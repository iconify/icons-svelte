<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qu5nzuxyh.css';
import '../../css/o/omzbjkw4i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="qu5nzuxyh"/><path class="omzbjkw4i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:vpn-policy" {...props}></Icon>
