<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/paef-ikde.css';
import '../../css/o/o04e0f4tg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":16};
const content = `<path class="paef-ikde"/><circle class="o04e0f4tg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="formkit:tag" {...props}></Icon>
