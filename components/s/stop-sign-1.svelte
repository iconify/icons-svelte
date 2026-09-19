<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hy_v726cn.css';
import '../../css/v/vz494t6ef.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hy_v726cn"/><path class="vz494t6ef"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:stop-sign-1" {...props}></Icon>
