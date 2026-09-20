<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o8d1ykbcg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o8d1ykbcg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:unlicense" {...props}></Icon>
