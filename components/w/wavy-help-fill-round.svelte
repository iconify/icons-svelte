<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zoo1k-bye.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zoo1k-bye"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:wavy-help-fill-round" {...props}></Icon>
