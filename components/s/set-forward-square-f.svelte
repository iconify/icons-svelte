<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sm52v9brw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<path class="sm52v9brw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:set-forward-square-f" {...props}></Icon>
