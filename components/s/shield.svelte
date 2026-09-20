<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kw89gnbud.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kw89gnbud"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:shield" {...props}></Icon>
