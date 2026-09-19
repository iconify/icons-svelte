<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jhr6axbos.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jhr6axbos"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:search-solid" {...props}></Icon>
