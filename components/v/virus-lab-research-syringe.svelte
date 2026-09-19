<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v-sbngbvh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="v-sbngbvh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:virus-lab-research-syringe" {...props}></Icon>
