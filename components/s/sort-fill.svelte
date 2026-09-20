<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g-p90obxp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="g-p90obxp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:sort-fill" {...props}></Icon>
