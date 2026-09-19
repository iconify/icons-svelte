<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qu8s29bva.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="qu8s29bva"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:wrench-small-filled" {...props}></Icon>
