<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/to8u9k8yb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="to8u9k8yb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:sd" {...props}></Icon>
