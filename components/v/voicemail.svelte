<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a1pc0bbci.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="a1pc0bbci"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wpf:voicemail" {...props}></Icon>
