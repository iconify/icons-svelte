<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z1s8-dbhh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="z1s8-dbhh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:shop-solid" {...props}></Icon>
