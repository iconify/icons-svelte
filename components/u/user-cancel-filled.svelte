<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mf9lx2b7f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mf9lx2b7f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:user-cancel-filled" {...props}></Icon>
