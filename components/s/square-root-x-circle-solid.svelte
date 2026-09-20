<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v-w-62byc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="v-w-62byc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:square-root-x-circle-solid" {...props}></Icon>
