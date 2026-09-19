<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ago-3bcco.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ago-3bcco"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:testicles" {...props}></Icon>
