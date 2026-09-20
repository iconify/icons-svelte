<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/koc1jcbel.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="koc1jcbel"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:starling-bank" {...props}></Icon>
