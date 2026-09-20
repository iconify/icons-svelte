<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oprlttbnf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oprlttbnf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:square-t" {...props}></Icon>
