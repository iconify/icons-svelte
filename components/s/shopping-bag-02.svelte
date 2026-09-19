<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j6u8l-oou.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j6u8l-oou"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:shopping-bag-02" {...props}></Icon>
