<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b_dd1bcgb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b_dd1bcgb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:user-marked-filled" {...props}></Icon>
