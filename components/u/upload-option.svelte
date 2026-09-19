<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h57zk-ypu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h57zk-ypu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:upload-option" {...props}></Icon>
