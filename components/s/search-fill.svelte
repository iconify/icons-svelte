<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hfik9abes.css';
import '../../css/t/tgpfh5wzi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hfik9abes"/><path clip-rule="evenodd" class="tgpfh5wzi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:search-fill" {...props}></Icon>
