<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/del6a6d2m.css';
import '../../css/l/lrkyxwbob.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="del6a6d2m"/><path class="lrkyxwbob"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:share-box-solid" {...props}></Icon>
