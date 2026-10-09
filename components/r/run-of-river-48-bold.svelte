<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q40h8-b-p.css';
import '../../css/w/wu_emw7zr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="q40h8-b-p"/><path class="wu_emw7zr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:run-of-river-48-bold" {...props}></Icon>
