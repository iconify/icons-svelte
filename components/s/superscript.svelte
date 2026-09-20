<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eavb5gb3x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="eavb5gb3x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:superscript" {...props}></Icon>
