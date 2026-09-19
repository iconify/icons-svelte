<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gpgd2ibzg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="gpgd2ibzg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:speaker-zzz" {...props}></Icon>
