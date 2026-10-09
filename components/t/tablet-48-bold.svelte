<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ecm4zwbye.css';
import '../../css/i/i23hwnb1g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ecm4zwbye"/><path class="i23hwnb1g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:tablet-48-bold" {...props}></Icon>
