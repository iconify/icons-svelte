<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mr80l3b1l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mr80l3b1l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:undo" {...props}></Icon>
