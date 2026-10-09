<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jbfaewbaw.css';
import '../../css/s/scknzcbae.css';
import '../../css/d/d672b0b5z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="jbfaewbaw"/><path class="scknzcbae"/><path class="d672b0b5z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:ship-48-bold" {...props}></Icon>
