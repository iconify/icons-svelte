<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sysz87b-k.css';
import '../../css/k/k5mfz-beo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="sysz87b-k"/><path class="k5mfz-beo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:workflow-48-bold" {...props}></Icon>
