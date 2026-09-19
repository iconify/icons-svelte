<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fl49b_58y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fl49b_58y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:trello-solid" {...props}></Icon>
