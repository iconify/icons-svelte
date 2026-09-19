<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c0dcn3bcc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c0dcn3bcc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:strike-through" {...props}></Icon>
