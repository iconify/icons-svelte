<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tp6hm53bn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tp6hm53bn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:siliconcloud-siliconflow" {...props}></Icon>
