<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qgx5ynb3r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qgx5ynb3r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:undo-24" {...props}></Icon>
