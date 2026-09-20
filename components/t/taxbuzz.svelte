<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cy8nyytvg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cy8nyytvg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:taxbuzz" {...props}></Icon>
