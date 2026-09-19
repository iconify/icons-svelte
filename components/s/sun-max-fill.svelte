<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pzzrj50-j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="pzzrj50-j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:sun-max-fill" {...props}></Icon>
