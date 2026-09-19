<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zfp75_bwr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path clip-rule="evenodd" class="zfp75_bwr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:zend" {...props}></Icon>
