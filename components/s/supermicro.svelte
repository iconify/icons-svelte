<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ugmf8pbol.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ugmf8pbol"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:supermicro" {...props}></Icon>
