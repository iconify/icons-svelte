<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uqywyhb5i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="uqywyhb5i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:sema" {...props}></Icon>
