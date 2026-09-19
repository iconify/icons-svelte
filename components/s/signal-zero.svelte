<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rxn_qk47p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rxn_qk47p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:signal-zero" {...props}></Icon>
