<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zdlqjf2ga.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zdlqjf2ga"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:rss-symbol-solid" {...props}></Icon>
