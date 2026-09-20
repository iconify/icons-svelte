<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ccrdiacgv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ccrdiacgv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:thumbtack-circle-filled" {...props}></Icon>
