<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/etcsyqc6c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="etcsyqc6c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:search-active" {...props}></Icon>
