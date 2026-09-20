<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/a/aq2e-nbuu.css';
import '../../css/b/bhi0ikx5y.css';
import '../../css/e/e7wls2wqe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="aq2e-nbuu"/><path class="bhi0ikx5y"/><path class="e7wls2wqe"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:shopping-basket-rating" {...props}></Icon>
