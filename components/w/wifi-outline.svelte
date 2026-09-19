<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/duuf9m24f.css';
import '../../css/g/gj0wcwb7j.css';
import '../../css/y/ym_5dj0al.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="duuf9m24f"/><path class="gj0wcwb7j"/><path class="ym_5dj0al"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:wifi-outline" {...props}></Icon>
