<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mjfcd84ht.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mjfcd84ht"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:share-bold" {...props}></Icon>
