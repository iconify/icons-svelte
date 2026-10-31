<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mc6_pdb7r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mc6_pdb7r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:table-cells-merge" {...props}></Icon>
