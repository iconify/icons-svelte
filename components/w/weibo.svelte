<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/by140xbel.css';
import '../../css/o/ow_ygzbys.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="by140xbel"/><path class="ow_ygzbys"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:weibo" {...props}></Icon>
