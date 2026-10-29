<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qk4pp05_i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qk4pp05_i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:wheat-solid" {...props}></Icon>
