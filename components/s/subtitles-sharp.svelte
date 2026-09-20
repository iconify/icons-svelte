<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tef0-zbpw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tef0-zbpw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:subtitles-sharp" {...props}></Icon>
