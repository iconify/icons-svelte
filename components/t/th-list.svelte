<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rwoeytogu.css';
import '../../css/c/cc3fl7wwz.css';
import '../../css/x/xul7skbaf.css';
import '../../css/k/k6fth3b8e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rwoeytogu"/><circle class="cc3fl7wwz"/><circle class="xul7skbaf"/><circle class="k6fth3b8e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:th-list" {...props}></Icon>
