<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i2ia5obuy.css';
import '../../css/u/umym_-bpi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i2ia5obuy"/><path clip-rule="evenodd" class="umym_-bpi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:server-outline" {...props}></Icon>
