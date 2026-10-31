<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eq8r75bol.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eq8r75bol"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:row-minus-round" {...props}></Icon>
