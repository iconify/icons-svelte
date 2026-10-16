<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dgvqv2bst.css';
import '../../css/v/vtc-cfb1t.css';
import '../../css/k/ka-2hq9em.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="dgvqv2bst"/><path class="vtc-cfb1t"/><path class="ka-2hq9em"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:tokamak-20" {...props}></Icon>
