<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h-lz6bbgg.css';
import '../../css/f/fewj64b-i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h-lz6bbgg"/><path class="fewj64b-i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:tab-external-24" {...props}></Icon>
