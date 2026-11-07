<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w_r2oob-p.css';
import '../../css/s/spvl3mbxz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w_r2oob-p"/><path class="spvl3mbxz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:square-academic-cap-2-outline" {...props}></Icon>
