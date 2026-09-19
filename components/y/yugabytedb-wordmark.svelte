<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o991c4n6k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="o991c4n6k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:yugabytedb-wordmark" {...props}></Icon>
