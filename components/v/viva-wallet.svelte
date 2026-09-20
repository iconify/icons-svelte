<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c5gwd2mku.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c5gwd2mku"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:viva-wallet" {...props}></Icon>
