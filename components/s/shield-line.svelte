<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qvjom7b2m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qvjom7b2m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:shield-line" {...props}></Icon>
