<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o1rt8ebqe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o1rt8ebqe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:search-bug" {...props}></Icon>
