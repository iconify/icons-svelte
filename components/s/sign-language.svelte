<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qfw2-nb3p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="qfw2-nb3p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:sign-language" {...props}></Icon>
