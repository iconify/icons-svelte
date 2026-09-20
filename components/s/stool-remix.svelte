<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/na_s0_b3p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="na_s0_b3p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:stool-remix" {...props}></Icon>
