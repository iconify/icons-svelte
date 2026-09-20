<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oh_1n6b9i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="oh_1n6b9i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:todo-done" {...props}></Icon>
