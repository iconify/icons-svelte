<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u07gqdk2e.css';
import '../../css/b/buahpzh7c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":24};
const content = `<path class="u07gqdk2e"/><path class="buahpzh7c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler-flags:vietnam" {...props}></Icon>
