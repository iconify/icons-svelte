<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mhp4b7gcv.css';
import '../../css/n/nos6nfben.css';
import '../../css/o/o4qtwp2ep.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mhp4b7gcv"/><path class="nos6nfben"/><path class="o4qtwp2ep"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:table" {...props}></Icon>
