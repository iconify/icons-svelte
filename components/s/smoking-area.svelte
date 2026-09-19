<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nnvqlybxk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nnvqlybxk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:smoking-area" {...props}></Icon>
