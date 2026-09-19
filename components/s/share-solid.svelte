<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x8w08ccil.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x8w08ccil"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:share-solid" {...props}></Icon>
