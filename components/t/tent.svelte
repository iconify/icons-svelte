<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/po4ve2bco.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="po4ve2bco"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:tent" {...props}></Icon>
