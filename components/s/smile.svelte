<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lda3vs_wa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":717,"height":698};
const content = `<path class="lda3vs_wa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:smile" {...props}></Icon>
