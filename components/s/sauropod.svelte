<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rpjp_c7is.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="rpjp_c7is"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:sauropod" {...props}></Icon>
