<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ef-yoed_f.css';
import '../../css/y/ymnh-3b0c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="ef-yoed_f"/><path class="ymnh-3b0c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:yugabytedb-wordmark" {...props}></Icon>
