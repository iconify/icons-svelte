<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oy08vwban.css';
import '../../css/h/hx5mj141a.css';
import '../../css/q/qxcq365rf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oy08vwban"/><path class="hx5mj141a"/><path class="qxcq365rf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:search-box-solid" {...props}></Icon>
