<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n3vu-5e0y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n3vu-5e0y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:smoke-detector-filled" {...props}></Icon>
