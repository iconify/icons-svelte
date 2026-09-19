<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i--4ambuk.css';
import '../../css/q/qzo006suv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<circle class="i--4ambuk"/><path class="qzo006suv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:sun-stroke-12" {...props}></Icon>
