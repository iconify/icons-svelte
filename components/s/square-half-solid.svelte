<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a-sx6ybrp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a-sx6ybrp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:square-half-solid" {...props}></Icon>
