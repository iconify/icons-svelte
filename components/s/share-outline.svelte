<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lun5-dx1a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lun5-dx1a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:share-outline" {...props}></Icon>
