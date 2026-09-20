<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nb-ml4nyg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nb-ml4nyg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:tree-catalog-filled" {...props}></Icon>
