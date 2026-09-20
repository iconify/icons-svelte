<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q2999kb9d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q2999kb9d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:setting-line" {...props}></Icon>
