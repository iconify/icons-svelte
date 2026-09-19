<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/duuf9m24f.css';
import '../../css/h/h8p6cfbln.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="duuf9m24f"/><path class="h8p6cfbln"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:wifi-off-outline" {...props}></Icon>
