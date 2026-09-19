<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tk4wyzbax.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tk4wyzbax"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:share-outline" {...props}></Icon>
