<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yw3xaacjo.css';
import '../../css/l/lb-veokpk.css';
import '../../css/g/g-6s3ptim.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="yw3xaacjo"/><path class="lb-veokpk"/><path class="g-6s3ptim"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:vegan-20" {...props}></Icon>
