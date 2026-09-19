<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fhxi0-bnb.css';
import '../../css/u/u3fkkvb-o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="fhxi0-bnb"/><path class="u3fkkvb-o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-color-icons:todo-list" {...props}></Icon>
