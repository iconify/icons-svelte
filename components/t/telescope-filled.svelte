<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bnk09y7es.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bnk09y7es"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:telescope-filled" {...props}></Icon>
