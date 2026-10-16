<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m-flw2bql.css';
import '../../css/i/ihgrfnbqw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="m-flw2bql"/><path class="ihgrfnbqw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:ups-48" {...props}></Icon>
