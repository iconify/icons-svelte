<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xcrbihbnd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xcrbihbnd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:sort-ascending-small-big" {...props}></Icon>
