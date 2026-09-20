<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pbh_n3bjd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="pbh_n3bjd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:user-multiple-group-solid" {...props}></Icon>
