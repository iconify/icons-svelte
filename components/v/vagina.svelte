<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ikal_ebue.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ikal_ebue"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:vagina" {...props}></Icon>
