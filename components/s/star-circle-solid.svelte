<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f7zbev1jn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="f7zbev1jn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:star-circle-solid" {...props}></Icon>
