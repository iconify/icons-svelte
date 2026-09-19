<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gl5lc-bqe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gl5lc-bqe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:rows-outline" {...props}></Icon>
