<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mnp81lbbc.css';
import '../../css/o/odno2sboo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mnp81lbbc"/><path class="odno2sboo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:sort-alpha-asc-24" {...props}></Icon>
