<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s63jr007d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s63jr007d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:settings-option" {...props}></Icon>
