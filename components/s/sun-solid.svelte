<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ilmv3rwlp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ilmv3rwlp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:sun-solid" {...props}></Icon>
