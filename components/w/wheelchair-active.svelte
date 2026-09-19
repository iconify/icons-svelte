<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kga6obbuj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kga6obbuj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:wheelchair-active" {...props}></Icon>
