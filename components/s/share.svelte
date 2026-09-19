<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sn9q4acno.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":788,"height":665};
const content = `<path class="sn9q4acno"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:share" {...props}></Icon>
