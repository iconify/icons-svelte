<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fv_9jiofm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fv_9jiofm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:table-rows-fill" {...props}></Icon>
