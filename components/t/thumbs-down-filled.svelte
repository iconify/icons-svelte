<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pb24y8btw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pb24y8btw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:thumbs-down-filled" {...props}></Icon>
