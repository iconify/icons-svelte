<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ocri5bbso.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ocri5bbso"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:shield-up" {...props}></Icon>
