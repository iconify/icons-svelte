<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h5b5ddvql.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="h5b5ddvql"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:vinyl2-filled" {...props}></Icon>
