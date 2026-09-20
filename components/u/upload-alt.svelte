<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/okq_komxg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="okq_komxg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:upload-alt" {...props}></Icon>
