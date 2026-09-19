<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kiqvv8bip.css';
import '../../css/o/o96_dt2bo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<circle class="kiqvv8bip"/><path class="o96_dt2bo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:sun-stroke-16" {...props}></Icon>
