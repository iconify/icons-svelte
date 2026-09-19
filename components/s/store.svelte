<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eer4ttwsv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eer4ttwsv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:store" {...props}></Icon>
