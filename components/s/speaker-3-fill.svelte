<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iawiiv2tu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="iawiiv2tu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:speaker-3-fill" {...props}></Icon>
