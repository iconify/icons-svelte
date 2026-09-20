<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b9uoqxdci.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b9uoqxdci"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:web3dotjs" {...props}></Icon>
