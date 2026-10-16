<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i_ml6hb0a.css';
import '../../css/g/g66uptbvs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="i_ml6hb0a"/><path class="g66uptbvs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:variable-resistor-48" {...props}></Icon>
