<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b5g66wbkc.css';
import '../../css/u/uk5liicmj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b5g66wbkc"/><path class="uk5liicmj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:yunohost" {...props}></Icon>
