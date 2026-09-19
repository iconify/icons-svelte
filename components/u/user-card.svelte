<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yltp1rbuh.css';
import '../../css/d/drnbxkbxp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="duoicon-secondary-layer yltp1rbuh"/><path class="drnbxkbxp duoicon-primary-layer"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="duo-icons:user-card" {...props}></Icon>
