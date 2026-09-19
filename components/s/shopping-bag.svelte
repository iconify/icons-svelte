<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/ho_irrb9b.css';
import '../../css/v/vzi465tms.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="duoicon-secondary-layer ho_irrb9b"/><path class="duoicon-primary-layer vzi465tms"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="duo-icons:shopping-bag" {...props}></Icon>
