<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k5098jv3v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k5098jv3v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:skip-forward-mini-fill" {...props}></Icon>
