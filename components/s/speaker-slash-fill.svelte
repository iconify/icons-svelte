<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iac53iaiu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="iac53iaiu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:speaker-slash-fill" {...props}></Icon>
