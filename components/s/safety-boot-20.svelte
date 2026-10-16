<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n3tl7xpsr.css';
import '../../css/t/t8tzpkb5n.css';
import '../../css/a/a196s7ber.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="n3tl7xpsr"/><path class="t8tzpkb5n"/><path class="a196s7ber"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:safety-boot-20" {...props}></Icon>
